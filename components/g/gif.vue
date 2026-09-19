<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7ywibcrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u7ywibcrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gif" /></template>
