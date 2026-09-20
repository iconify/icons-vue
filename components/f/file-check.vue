<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/ud20_tc4b.css';
import '../../css/m/moorkb8oa.css';
import '../../css/m/mz2593bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ud20_tc4b"/><path class="moorkb8oa"/><path class="mz2593bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-check" /></template>
