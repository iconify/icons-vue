<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inr8_8btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="inr8_8btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:binoculars" /></template>
