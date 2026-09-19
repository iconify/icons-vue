<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/u/u4gjvmm-i.css';
import '../../css/w/wzezone-a.css';
import '../../css/h/hozl91a5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="u4gjvmm-i"/><path class="wzezone-a"/><path class="hozl91a5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:collection-records" /></template>
