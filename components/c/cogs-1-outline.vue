<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zx7uv5q7n.css';
import '../../css/f/f_mfzu3uv.css';
import '../../css/y/yu-13qbwi.css';
import '../../css/g/gablpk-so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zx7uv5q7n"/><path class="f_mfzu3uv"/><path class="yu-13qbwi"/><path class="gablpk-so"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cogs-1-outline" /></template>
