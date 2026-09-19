<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il99x8wzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="il99x8wzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-dd" /></template>
