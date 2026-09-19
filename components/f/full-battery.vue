<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shnc5m5hf.css';
import '../../css/c/cn4m4xbfq.css';
import '../../css/a/a1x6v0wfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="shnc5m5hf"><path class="cn4m4xbfq"/><path class="a1x6v0wfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:full-battery" /></template>
