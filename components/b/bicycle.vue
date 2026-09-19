<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk70g6bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zk70g6bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bicycle" /></template>
