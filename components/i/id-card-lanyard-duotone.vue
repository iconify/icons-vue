<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l72e9vj4g.css';
import '../../css/u/uh3jeubfp.css';
import '../../css/a/aw_ok7bnp.css';
import '../../css/w/wkwew6efo.css';
import '../../css/i/i3sr6la4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l72e9vj4g"/><path class="uh3jeubfp"/><path class="aw_ok7bnp"/><path class="wkwew6efo"/><path class="i3sr6la4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:id-card-lanyard-duotone" /></template>
