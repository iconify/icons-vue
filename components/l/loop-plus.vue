<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o8tzs_jpg.css';
import '../../css/r/ro1ygcb6e.css';
import '../../css/n/nivlo-u6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="o8tzs_jpg"/><path class="ro1ygcb6e"/><path class="nivlo-u6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:loop-plus" /></template>
