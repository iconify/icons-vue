<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c65wh9has.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c65wh9has"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-chart-bar" /></template>
