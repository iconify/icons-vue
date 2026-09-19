<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq9s03bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tq9s03bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-milvus" /></template>
