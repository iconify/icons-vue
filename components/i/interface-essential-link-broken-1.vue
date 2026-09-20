<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j946aj-jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j946aj-jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-link-broken-1" /></template>
