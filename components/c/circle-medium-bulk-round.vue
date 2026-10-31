<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-5xk6bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-5xk6bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-medium-bulk-round" /></template>
