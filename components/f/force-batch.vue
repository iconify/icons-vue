<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8kce2a0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m8kce2a0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:force-batch" /></template>
