<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlk0_mb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlk0_mb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-more-fill" /></template>
