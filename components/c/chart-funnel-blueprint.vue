<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/f6lqbsbnv.css';
import '../../css/r/rylunibdb.css';
import '../../css/n/nge5cfbll.css';
import '../../css/o/of9jv2dlw.css';
import '../../css/f/flbsvpbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="f6lqbsbnv wm-deco"/><path class="rylunibdb wm-deco"/><path class="nge5cfbll wm-deco"/><path class="of9jv2dlw wm-k"/><path class="flbsvpbyj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-funnel-blueprint" /></template>
