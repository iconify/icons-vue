<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co8bl-j7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="co8bl-j7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bow-and-arrow-bold" /></template>
