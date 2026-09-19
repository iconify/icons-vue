<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr298zbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr298zbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-redbubble" /></template>
