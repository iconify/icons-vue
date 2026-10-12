<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb96ptbmh.css';
import '../../css/n/n_yelj1ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tb96ptbmh"/><path class="n_yelj1ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gps-20-bold" /></template>
