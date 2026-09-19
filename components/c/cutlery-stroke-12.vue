<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chu0w4bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="chu0w4bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cutlery-stroke-12" /></template>
