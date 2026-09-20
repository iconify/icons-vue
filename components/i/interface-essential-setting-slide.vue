<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk4zobbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rk4zobbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-setting-slide" /></template>
