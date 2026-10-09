<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee5vtnbjr.css';
import '../../css/h/hxpk5bbgt.css';
import '../../css/f/fo22hzbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ee5vtnbjr"/><path class="hxpk5bbgt"/><path class="fo22hzbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-flow-20" /></template>
