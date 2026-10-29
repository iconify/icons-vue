<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/e/ehc23t72p.css';
import '../../css/f/fsk0ki2ik.css';
import '../../css/y/yi1bneumz.css';
import '../../css/f/fxkd8kbag.css';
import '../../css/j/jqfn8_bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ehc23t72p wm-deco"/><path class="fsk0ki2ik wm-deco"/><path class="wm-deco yi1bneumz"/><path class="fxkd8kbag wm-k"/><path class="jqfn8_bps wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-koala-blueprint" /></template>
