<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbubq_bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qbubq_bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-list" /></template>
