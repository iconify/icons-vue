<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo65a95px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bo65a95px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:agriculture-analytics" /></template>
