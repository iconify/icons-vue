<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sto5bkbur.css';
import '../../css/y/yrmlhdbfc.css';
import '../../css/e/ep-2nyeek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="sto5bkbur"><path class="yrmlhdbfc"/><path class="ep-2nyeek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:arduino" /></template>
