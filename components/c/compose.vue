<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er92zo0ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="er92zo0ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:compose" /></template>
