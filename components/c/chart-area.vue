<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve2w2-b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ve2w2-b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chart-area" /></template>
