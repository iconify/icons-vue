<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/k22l5nm1h.css';
import '../../css/u/uwftcyb8e.css';
import '../../css/v/v8h5vrbeb.css';
import '../../css/y/ysqxkebtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k22l5nm1h"/><path class="uwftcyb8e"/><path class="v8h5vrbeb"/><path class="ysqxkebtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:camera-off-sharp-duotone" /></template>
