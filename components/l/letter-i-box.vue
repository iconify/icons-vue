<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymm5thzlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymm5thzlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-i-box" /></template>
