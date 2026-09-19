<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un6md_v2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="un6md_v2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrange-vertical" /></template>
