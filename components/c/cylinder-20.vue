<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbe-aclic.css';
import '../../css/i/iv-96i7pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cbe-aclic"/><path class="iv-96i7pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cylinder-20" /></template>
