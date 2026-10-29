<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/k1ewr4bgn.css';
import '../../css/m/mf03hhbbg.css';
import '../../css/i/i0gy4iser.css';
import '../../css/p/pmhci7c4q.css';
import '../../css/l/l6x6q3i-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="k1ewr4bgn wm-deco"/><path class="mf03hhbbg wm-deco"/><path class="i0gy4iser wm-k"/><path class="pmhci7c4q wm-a"/><path class="l6x6q3i-w wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-blueprint" /></template>
