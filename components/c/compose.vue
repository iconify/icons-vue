<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpv-gzbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jpv-gzbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:compose" /></template>
