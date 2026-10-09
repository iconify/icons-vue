<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8grm_bir.css';
import '../../css/m/mh0v8zovj.css';
import '../../css/j/jsxzfjb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h8grm_bir"/><path class="mh0v8zovj"/><path class="jsxzfjb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geothermal-plant-20-bold" /></template>
