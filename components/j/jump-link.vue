<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a00qgcwyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a00qgcwyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:jump-link" /></template>
