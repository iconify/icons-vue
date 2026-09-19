<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zsy9hqdwb.css';
import '../../css/r/rgza8wbpy.css';
import '../../css/q/qkhof_b-k.css';
import '../../css/l/luw467qkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zsy9hqdwb"/><path class="rgza8wbpy"/><path class="qkhof_b-k"/><path class="luw467qkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-layout-4-outline" /></template>
