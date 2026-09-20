<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/pcl3d89qc.css';
import '../../css/l/la7gkwdbc.css';
import '../../css/n/nv0xecb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pcl3d89qc"/><path class="la7gkwdbc"/><path class="nv0xecb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-off-sharp-two-tone" /></template>
