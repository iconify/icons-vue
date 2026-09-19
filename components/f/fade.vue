<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5sg82bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d5sg82bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fade" /></template>
