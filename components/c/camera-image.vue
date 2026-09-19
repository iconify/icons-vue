<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/y5ywfkbiz.css';
import '../../css/n/nb60d5bfg.css';
import '../../css/l/lg_mi-u6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y5ywfkbiz"/><circle class="nb60d5bfg"/><path class="lg_mi-u6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:camera-image" /></template>
