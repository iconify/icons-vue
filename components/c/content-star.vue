<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hglly4p7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hglly4p7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-star" /></template>
