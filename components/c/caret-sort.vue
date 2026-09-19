<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cya-rzp4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cya-rzp4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:caret-sort" /></template>
