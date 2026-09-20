<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4xf36ii.css';
import '../../css/y/yp70zv-ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bp4xf36ii"/><path class="yp70zv-ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-graphic-tablet-draw" /></template>
