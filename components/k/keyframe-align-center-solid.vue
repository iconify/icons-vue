<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-l1pd0_w.css';
import '../../css/m/m7zxsgbcu.css';
import '../../css/x/xg7awccao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path class="m7zxsgbcu"/><path clip-rule="evenodd" class="xg7awccao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframe-align-center-solid" /></template>
