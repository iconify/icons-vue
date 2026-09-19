<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi_glab8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yi_glab8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:airline-digital-gate" /></template>
