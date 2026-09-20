<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa4bx0bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xa4bx0bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dashboard-circle" /></template>
