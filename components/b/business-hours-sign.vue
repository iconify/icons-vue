<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8ybwbcwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w8ybwbcwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:business-hours-sign" /></template>
