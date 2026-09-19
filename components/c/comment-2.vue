<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jbrmr6bbt.css';
import '../../css/b/b63-0qqnv.css';
import '../../css/h/h_macgb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jbrmr6bbt"/><path class="b63-0qqnv"/><rect class="h_macgb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:comment-2" /></template>
