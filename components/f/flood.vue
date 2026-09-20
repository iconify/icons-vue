<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7_hf0wim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="i7_hf0wim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:flood" /></template>
