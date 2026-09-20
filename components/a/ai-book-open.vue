<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ni1ex1sbr.css';
import '../../css/l/ldpo4n3qb.css';
import '../../css/u/ubtuxebtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ni1ex1sbr"/><path class="ldpo4n3qb"/><path class="ubtuxebtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-book-open" /></template>
