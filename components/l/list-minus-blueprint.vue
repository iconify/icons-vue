<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/x/xr14t48pc.css';
import '../../css/w/wmx-00bdf.css';
import '../../css/n/n2_r2ubps.css';
import '../../css/o/okp7pp4nk.css';
import '../../css/s/sxwvjhaxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco xr14t48pc"/><path class="wm-deco wmx-00bdf"/><path class="n2_r2ubps wm-k"/><path class="okp7pp4nk wm-s"/><path class="sxwvjhaxj wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-minus-blueprint" /></template>
