<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6-49njwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6-49njwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:end" /></template>
