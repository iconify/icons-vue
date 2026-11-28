<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tap15_bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tap15_bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-plus-fill" /></template>
