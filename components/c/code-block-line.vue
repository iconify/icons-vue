<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chu4txbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chu4txbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:code-block-line" /></template>
