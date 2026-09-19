<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg7uqob8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yg7uqob8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:auto" /></template>
