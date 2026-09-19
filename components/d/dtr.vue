<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/kpi2fzh0j.css';
import '../../css/b/b0h_shk9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="kpi2fzh0j"/><path class="b0h_shk9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dtr" /></template>
