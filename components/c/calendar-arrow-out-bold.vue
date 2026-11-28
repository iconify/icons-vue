<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx9mvqppf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tx9mvqppf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-arrow-out-bold" /></template>
