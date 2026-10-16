<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxz-0ibrd.css';
import '../../css/a/aycw-jbph.css';
import '../../css/j/jeyqzjnhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oxz-0ibrd"/><path class="aycw-jbph"/><path class="jeyqzjnhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-battery-alert-20-bold" /></template>
