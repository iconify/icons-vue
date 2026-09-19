<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o799rcisc.css';
import '../../css/d/dufseh5oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":32};
const content = `<g class="cuyn6tgcc"><path class="o799rcisc"/><path class="dufseh5oc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:caution" /></template>
