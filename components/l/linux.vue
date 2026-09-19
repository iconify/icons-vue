<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb3q0tz5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sb3q0tz5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:linux" /></template>
