<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvaiqfbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1536};
const content = `<path class="rvaiqfbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:code-fork" /></template>
