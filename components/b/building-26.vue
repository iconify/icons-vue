<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_x215gla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="t_x215gla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:building-26" /></template>
