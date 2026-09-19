<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noj10xq_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="noj10xq_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:globe-showing-americas" /></template>
