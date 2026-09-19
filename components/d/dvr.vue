<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9jxs0bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9jxs0bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dvr" /></template>
