<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srp8_lblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="srp8_lblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cubes-stacked" /></template>
