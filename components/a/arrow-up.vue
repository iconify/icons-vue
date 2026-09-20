<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlw-j5ziv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mlw-j5ziv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-up" /></template>
