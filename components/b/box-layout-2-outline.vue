<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yeujkhbau.css';
import '../../css/r/rgza8wbpy.css';
import '../../css/k/krcyms04q.css';
import '../../css/l/luw467qkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yeujkhbau"/><path class="rgza8wbpy"/><path class="krcyms04q"/><path class="luw467qkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-layout-2-outline" /></template>
