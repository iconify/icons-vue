<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akk0b-1ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="akk0b-1ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:formatting" /></template>
