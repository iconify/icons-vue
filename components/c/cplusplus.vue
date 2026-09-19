<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3ibzzb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d3ibzzb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cplusplus" /></template>
