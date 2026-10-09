<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w17z9ibyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w17z9ibyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:couple-20-bold" /></template>
