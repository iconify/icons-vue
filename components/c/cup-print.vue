<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/ge3ashgyr.css';
import '../../css/s/sxi3o6mdr.css';
import '../../css/y/yzw7bhduj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ge3ashgyr"/><path clip-rule="evenodd" class="sxi3o6mdr"/><path class="yzw7bhduj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:cup-print" /></template>
