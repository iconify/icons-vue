<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/n067cabcj.css';
import '../../css/s/snibgdcaa.css';
import '../../css/v/vqjoaw6-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n067cabcj"/><path class="snibgdcaa"/><path class="vqjoaw6-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-sparkles-sharp-two-tone" /></template>
