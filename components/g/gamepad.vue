<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/unnw82k4d.css';
import '../../css/m/m4577_bii.css';
import '../../css/d/d3xpk_fla.css';
import '../../css/p/p34h9gxaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="unnw82k4d"/><path class="m4577_bii"/><path clip-rule="evenodd" class="d3xpk_fla"/><path class="p34h9gxaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:gamepad" /></template>
