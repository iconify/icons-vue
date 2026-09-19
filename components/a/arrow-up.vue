<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn7avwbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":630,"height":700};
const content = `<path class="zn7avwbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:arrow-up" /></template>
