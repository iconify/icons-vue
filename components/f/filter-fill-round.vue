<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcc8lpl6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcc8lpl6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-fill-round" /></template>
