<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2f2jl93k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2f2jl93k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hollo-light" /></template>
