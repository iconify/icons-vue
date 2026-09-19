<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwyy-sbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uwyy-sbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-governance-lifecycle" /></template>
