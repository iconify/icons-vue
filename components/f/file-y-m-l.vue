<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2nx3gbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p2nx3gbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:file-y-m-l" /></template>
