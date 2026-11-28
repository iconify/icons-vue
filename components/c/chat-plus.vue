<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xihhgf-iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xihhgf-iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-plus" /></template>
