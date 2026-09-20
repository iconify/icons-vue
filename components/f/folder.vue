<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtz13ylql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xtz13ylql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder" /></template>
