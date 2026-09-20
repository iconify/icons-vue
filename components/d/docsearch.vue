<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1mjunbsu.css';
import '../../css/v/vn8sbhbcq.css';
import '../../css/e/e6yrqacor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1mjunbsu"><path class="vn8sbhbcq"/><path class="e6yrqacor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:docsearch" /></template>
