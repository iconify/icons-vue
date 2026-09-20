<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjx1gv_9g.css';
import '../../css/a/aavawy-uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kjx1gv_9g"/><path class="aavawy-uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:jar" /></template>
