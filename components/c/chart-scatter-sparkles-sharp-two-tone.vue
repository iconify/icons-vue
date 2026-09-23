<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jtkvb9fgt.css';
import '../../css/y/yp8xy3bjb.css';
import '../../css/y/yb8pm2b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jtkvb9fgt"/><path class="yp8xy3bjb"/><path class="yb8pm2b6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-scatter-sparkles-sharp-two-tone" /></template>
