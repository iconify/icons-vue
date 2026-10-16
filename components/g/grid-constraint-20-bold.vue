<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6bewdbru.css';
import '../../css/l/lm0-7bbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m6bewdbru"/><path class="lm0-7bbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-constraint-20-bold" /></template>
