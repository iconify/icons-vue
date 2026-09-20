<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqvh32bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zqvh32bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:atlas" /></template>
