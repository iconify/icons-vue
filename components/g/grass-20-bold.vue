<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fad7f9tkf.css';
import '../../css/n/nq0-d_lbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fad7f9tkf"/><path class="nq0-d_lbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grass-20-bold" /></template>
