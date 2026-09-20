<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt4villyt.css';
import '../../css/d/di3yhtbnj.css';
import '../../css/z/zzmgb2sjr.css';
import '../../css/r/rv4rd8b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jt4villyt"/><g class="di3yhtbnj"><path clip-rule="evenodd" class="zzmgb2sjr"/><path class="rv4rd8b8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:layers-more-16" /></template>
