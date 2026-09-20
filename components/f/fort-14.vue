<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxdldqbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hxdldqbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:fort-14" /></template>
