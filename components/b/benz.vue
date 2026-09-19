<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/x/xlg4h1uyo.css';
import '../../css/b/bazc4or7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="y6f0jibvm"/><path class="xlg4h1uyo"/><path class="bazc4or7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:benz" /></template>
