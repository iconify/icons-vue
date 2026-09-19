<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rl15_ykyd.css';
import '../../css/g/g1gkzeb7t.css';
import '../../css/b/bndlp9bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":90,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rl15_ykyd"/><path class="g1gkzeb7t"/><path class="bndlp9bpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:cogs-1" /></template>
