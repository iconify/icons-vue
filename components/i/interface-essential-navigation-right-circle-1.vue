<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke40b1uoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ke40b1uoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-navigation-right-circle-1" /></template>
