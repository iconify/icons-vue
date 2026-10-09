<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-wcb8bfh.css';
import '../../css/i/iuu9occ8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a-wcb8bfh"/><path class="iuu9occ8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-price-20-bold" /></template>
