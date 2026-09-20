<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sk1228b2x.css';
import '../../css/e/ezshh0bgn.css';
import '../../css/l/lum82dbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sk1228b2x"/><path class="ezshh0bgn"/><path class="lum82dbar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:exit-line-duotone" /></template>
