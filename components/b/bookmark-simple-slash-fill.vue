<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1x3a2bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h1x3a2bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-slash-fill" /></template>
