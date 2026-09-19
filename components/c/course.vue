<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrrdj-bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vrrdj-bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:course" /></template>
