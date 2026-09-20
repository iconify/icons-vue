<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4d4uacpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k4d4uacpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:arrow-move-flat" /></template>
