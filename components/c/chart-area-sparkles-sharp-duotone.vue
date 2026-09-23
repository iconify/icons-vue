<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/q/q0ankg4uz.css';
import '../../css/g/gri0ybjpd.css';
import '../../css/y/yb8pm2b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q0ankg4uz"/><path class="gri0ybjpd"/><path class="yb8pm2b6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-area-sparkles-sharp-duotone" /></template>
