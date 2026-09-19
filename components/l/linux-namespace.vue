<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4min-bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m4min-bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:linux-namespace" /></template>
