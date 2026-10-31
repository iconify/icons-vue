<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc0tz1cqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0tz1cqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-from-line-fill-round" /></template>
