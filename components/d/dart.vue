<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z05ebsmne.css';
import '../../css/n/nisslya0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="z05ebsmne"/><path class="nisslya0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dart" /></template>
