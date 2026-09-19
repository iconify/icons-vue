<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tkz1d8fvs.css';
import '../../css/a/axl_d5b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="tkz1d8fvs"/><path clip-rule="evenodd" class="axl_d5b5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:circle-print" /></template>
