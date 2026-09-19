<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g87_r8bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="g87_r8bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:border-all" /></template>
