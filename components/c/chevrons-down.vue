<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/m/mu8p_tbuc.css';
import '../../css/q/qgoo28zqg.css';
import '../../css/l/lskufrbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="mu8p_tbuc wm-k"/><path class="qgoo28zqg wm-a"/><path class="lskufrbgk wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:chevrons-down" /></template>
