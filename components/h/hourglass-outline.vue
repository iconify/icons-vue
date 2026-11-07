<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbuco0-ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbuco0-ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hourglass-outline" /></template>
