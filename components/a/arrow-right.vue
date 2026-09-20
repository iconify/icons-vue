<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxlvxlbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qxlvxlbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:arrow-right" /></template>
