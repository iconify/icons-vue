<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i49qbib-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i49qbib-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-align-center" /></template>
