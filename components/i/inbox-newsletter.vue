<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsgjkwuzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rsgjkwuzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inbox-newsletter" /></template>
