<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy6cbetxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iy6cbetxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:join-outer" /></template>
