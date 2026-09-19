<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnbk1wqaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rnbk1wqaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:file-h-t-m-l" /></template>
