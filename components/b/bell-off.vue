<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/ei8g9bc3n.css';
import '../../css/g/gs9k1ghcu.css';
import '../../css/k/kipcp4bhv.css';
import '../../css/g/g25vtgbhi.css';
import '../../css/v/vvx5zcbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ei8g9bc3n wm-shadow"/><path class="gs9k1ghcu wm-shadow"/><path class="kipcp4bhv"/><path class="g25vtgbhi"/><path class="vvx5zcbvx wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:bell-off" /></template>
