<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c35hgrb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c35hgrb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-scroll-horizontal" /></template>
