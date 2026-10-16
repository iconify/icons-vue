<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev30ibc3d.css';
import '../../css/d/dlfk2kx2y.css';
import '../../css/f/feh6r_b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ev30ibc3d"/><path class="dlfk2kx2y"/><path class="feh6r_b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:elevator-20-bold" /></template>
