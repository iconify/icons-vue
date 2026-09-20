<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgxm9rbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgxm9rbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eraser2-filled" /></template>
