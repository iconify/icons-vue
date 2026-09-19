<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j78zgrbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j78zgrbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:format-status" /></template>
