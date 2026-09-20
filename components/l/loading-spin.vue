<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p14lm7b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p14lm7b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:loading-spin" /></template>
