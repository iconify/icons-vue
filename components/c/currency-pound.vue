<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfe5p0b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xfe5p0b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-pound" /></template>
