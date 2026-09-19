<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_y7vvb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_y7vvb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:invoice-bold" /></template>
