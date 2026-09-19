<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/ojnvnib6l.css';
import '../../css/p/pg-pw1_lh.css';
import '../../css/z/z3u09jb2h.css';
import '../../css/i/i6q05pbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ojnvnib6l"/><path class="pg-pw1_lh"/><path class="z3u09jb2h"/><path class="i6q05pbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:die-4-outline" /></template>
