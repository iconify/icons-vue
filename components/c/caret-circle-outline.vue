<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a3x0u_b2g.css';
import '../../css/y/yev7me0jl.css';
import '../../css/l/l38-skyep.css';
import '../../css/h/h71ihjbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a3x0u_b2g"/><path class="yev7me0jl"/><path class="l38-skyep"/><path class="h71ihjbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:caret-circle-outline" /></template>
