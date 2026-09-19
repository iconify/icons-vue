<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8a8omblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y8a8omblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:home" /></template>
