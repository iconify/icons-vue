<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/luygz3g7s.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/z/z_xkh2b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="luygz3g7s"/><path class="p53xcyb3q"/><path class="z_xkh2b7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-network-sharp-two-tone" /></template>
