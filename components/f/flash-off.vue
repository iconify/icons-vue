<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xwiyftz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w4xwiyftz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flash-off" /></template>
