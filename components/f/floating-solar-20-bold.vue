<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5zz3vvln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v5zz3vvln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:floating-solar-20-bold" /></template>
