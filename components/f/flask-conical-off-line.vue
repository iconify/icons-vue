<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce6p3zbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce6p3zbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-conical-off-line" /></template>
