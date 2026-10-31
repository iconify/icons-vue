<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/m/mw_sj1dvg.css';
import '../../css/y/yrnv22bjh.css';
import '../../css/c/cctzrl-0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="mw_sj1dvg"/><path class="yrnv22bjh"/><path class="cctzrl-0g wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:bone" /></template>
