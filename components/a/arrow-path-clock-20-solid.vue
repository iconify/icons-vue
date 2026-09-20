<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv_vv6bcm.css';
import '../../css/f/fe1xdgb8o.css';
import '../../css/n/nxo_13i2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="nv_vv6bcm"><path class="fe1xdgb8o"/><path class="nxo_13i2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-clock-20-solid" /></template>
