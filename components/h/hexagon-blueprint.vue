<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/sp_mmnh0l.css';
import '../../css/n/nylww15uo.css';
import '../../css/t/t218te2ox.css';
import '../../css/r/r2v_q5qdx.css';
import '../../css/t/t3r3bvyth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="sp_mmnh0l wm-deco"/><path class="nylww15uo wm-deco"/><path class="t218te2ox wm-deco"/><path class="r2v_q5qdx wm-k"/><path class="t3r3bvyth wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hexagon-blueprint" /></template>
