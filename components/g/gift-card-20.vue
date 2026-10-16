<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4l8cxbpg.css';
import '../../css/k/kvj1fs-np.css';
import '../../css/d/dw7wi78ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t4l8cxbpg"/><path class="kvj1fs-np"/><path class="dw7wi78ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gift-card-20" /></template>
