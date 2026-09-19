<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnddkxf3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnddkxf3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-chevron-down" /></template>
