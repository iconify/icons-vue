<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij_yecsrd.css';
import '../../css/i/ihj0a5_zp.css';
import '../../css/r/r8m749-bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ij_yecsrd"/><path class="ihj0a5_zp"/><path class="r8m749-bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:district-heating-20-bold" /></template>
