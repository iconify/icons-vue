<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv5kgg-ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sv5kgg-ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:distribute-vertical-center" /></template>
