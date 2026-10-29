<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/sqxgxfx8j.css';
import '../../css/o/o3ggb2czz.css';
import '../../css/o/oa8wtcqrr.css';
import '../../css/t/t-snm5blv.css';
import '../../css/l/l-9css3lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="sqxgxfx8j wm-deco"/><path class="o3ggb2czz wm-deco"/><path class="oa8wtcqrr wm-k"/><path class="t-snm5blv wm-a"/><path class="l-9css3lp wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-down-blueprint" /></template>
