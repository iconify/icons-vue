<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t18l-9bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t18l-9bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-waterfall-round" /></template>
