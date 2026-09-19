<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/louu8cbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="louu8cbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:concept" /></template>
