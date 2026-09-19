<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_aohhbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="j_aohhbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-ltr" /></template>
