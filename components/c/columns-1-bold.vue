<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/d/d7ze-3byf.css';
import '../../css/v/v8921wpmq.css';
import '../../css/a/auk98ibeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><path class="d7ze-3byf"/><rect class="v8921wpmq"/><path class="auk98ibeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:columns-1-bold" /></template>
