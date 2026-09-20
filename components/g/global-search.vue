<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jsy9-fwnj.css';
import '../../css/v/vemdn0bqs.css';
import '../../css/b/bcn2hfbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jsy9-fwnj"/><path class="vemdn0bqs"/><path class="bcn2hfbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:global-search" /></template>
