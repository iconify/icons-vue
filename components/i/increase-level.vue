<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ha7ibzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0ha7ibzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:increase-level" /></template>
