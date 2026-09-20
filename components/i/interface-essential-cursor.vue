<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgway08yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rgway08yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-cursor" /></template>
