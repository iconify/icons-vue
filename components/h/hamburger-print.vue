<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fg-4bjb3w.css';
import '../../css/b/blnixl87k.css';
import '../../css/w/wx8fs402j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="fg-4bjb3w"/><path clip-rule="evenodd" class="blnixl87k"/><path class="wx8fs402j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:hamburger-print" /></template>
