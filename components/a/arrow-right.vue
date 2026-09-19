<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/o7go62bvs.css';
import '../../css/r/r74jfkeku.css';
import '../../css/w/wtwsfcbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="o7go62bvs"/><path class="r74jfkeku"/><path class="wtwsfcbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-right" /></template>
