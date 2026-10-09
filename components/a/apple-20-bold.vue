<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg0icab7b.css';
import '../../css/y/ybggmtbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qg0icab7b"/><path class="ybggmtbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:apple-20-bold" /></template>
