<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_ezx1bzs.css';
import '../../css/f/f46-hd4vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_ezx1bzs"/><path class="f46-hd4vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-budget-20-bold" /></template>
