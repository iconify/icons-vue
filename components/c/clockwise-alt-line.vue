<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccxj3j0_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccxj3j0_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clockwise-alt-line" /></template>
