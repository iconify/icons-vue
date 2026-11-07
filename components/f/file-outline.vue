<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0zncejna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0zncejna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-outline" /></template>
