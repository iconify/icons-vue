<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-xi7c3pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-xi7c3pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-rupee-fill-round" /></template>
