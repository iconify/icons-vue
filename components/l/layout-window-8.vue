<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8hsnibud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d8hsnibud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-8" /></template>
