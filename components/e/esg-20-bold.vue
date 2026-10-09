<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdw3vx8xp.css';
import '../../css/j/j-4k2f7vu.css';
import '../../css/w/w3544mb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fdw3vx8xp"/><path class="j-4k2f7vu"/><path class="w3544mb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:esg-20-bold" /></template>
