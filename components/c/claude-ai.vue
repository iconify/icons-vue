<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-k-cebwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-k-cebwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:claude-ai" /></template>
