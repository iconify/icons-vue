<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/da795db8g.css';
import '../../css/w/wl3vkgwgq.css';
import '../../css/r/rat7bsbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="da795db8g"/><path class="wl3vkgwgq wm-shadow"/><path class="rat7bsbmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-right-engrave" /></template>
