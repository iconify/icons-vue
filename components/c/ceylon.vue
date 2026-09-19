<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mk7e45w8q.css';
import '../../css/q/qoj1bdcyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="mk7e45w8q"/><path class="qoj1bdcyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ceylon" /></template>
