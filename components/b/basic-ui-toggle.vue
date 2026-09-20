<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-pocwb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h-pocwb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-toggle" /></template>
