<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9ck89bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="i9ck89bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:direction-right" /></template>
