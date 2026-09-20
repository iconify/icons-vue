<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulg-h6bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ulg-h6bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:human-on-ferry" /></template>
