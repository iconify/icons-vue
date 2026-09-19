<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlpp7qqxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zlpp7qqxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-right" /></template>
