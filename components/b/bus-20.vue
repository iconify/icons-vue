<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4r3ojbrq.css';
import '../../css/c/ccfx0hgsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g4r3ojbrq"/><path class="ccfx0hgsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bus-20" /></template>
