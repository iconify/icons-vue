<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dr81gjbdd.css';
import '../../css/h/h4_frbcfb.css';
import '../../css/q/qmhuddb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dr81gjbdd"/><circle class="h4_frbcfb"/><path class="qmhuddb0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:anchor" /></template>
