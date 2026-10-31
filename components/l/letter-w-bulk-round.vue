<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-r9umawa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-r9umawa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-w-bulk-round" /></template>
