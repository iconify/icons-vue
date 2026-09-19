<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8ajbwbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8ajbwbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cannabis" /></template>
