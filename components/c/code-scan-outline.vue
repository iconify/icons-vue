<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3f0a4bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3f0a4bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-scan-outline" /></template>
