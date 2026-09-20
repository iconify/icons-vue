<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfq67mvgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hfq67mvgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inline-right" /></template>
