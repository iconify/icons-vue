<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8jmq4o5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="s8jmq4o5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:graph-box" /></template>
