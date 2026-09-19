<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3kq37bng.css';
import '../../css/x/xqe6h1fjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i3kq37bng"/><path class="xqe6h1fjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-datastage" /></template>
