<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5zec1bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y5zec1bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:dice" /></template>
