<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1s6nvbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v1s6nvbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:goodreads" /></template>
