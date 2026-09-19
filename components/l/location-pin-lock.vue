<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy7z0yolq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cy7z0yolq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:location-pin-lock" /></template>
