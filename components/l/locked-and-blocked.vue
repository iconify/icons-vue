<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvzxvjb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vvzxvjb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:locked-and-blocked" /></template>
