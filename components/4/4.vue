<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4xrz4bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="j4xrz4bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:4" /></template>
