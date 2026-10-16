<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxz-0ibrd.css';
import '../../css/a/aycw-jbph.css';
import '../../css/l/l3qindbue.css';
import '../../css/f/fdtytm4ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oxz-0ibrd"/><path class="aycw-jbph"/><path class="l3qindbue"/><path class="fdtytm4ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-battery-x-20-bold" /></template>
