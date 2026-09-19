<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gv1rnmbhg.css';
import '../../css/l/l2q3qg5ur.css';
import '../../css/j/j5ytutb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="gv1rnmbhg"/><path clip-rule="evenodd" class="l2q3qg5ur"/><path clip-rule="evenodd" class="j5ytutb_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-atlas-bold" /></template>
