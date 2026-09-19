<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hine55bkd.css';
import '../../css/e/e00g5nbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hine55bkd"/><path class="e00g5nbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-sentiment" /></template>
