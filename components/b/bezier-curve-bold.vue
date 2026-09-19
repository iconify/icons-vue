<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aq0x21h-i.css';
import '../../css/d/dpafqgbph.css';
import '../../css/v/vja-mbcsd.css';
import '../../css/l/lw-kuab_s.css';
import '../../css/x/xs5iv-0fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="aq0x21h-i"/><path class="dpafqgbph"/><path class="vja-mbcsd"/><circle class="lw-kuab_s"/><circle class="xs5iv-0fy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-curve-bold" /></template>
