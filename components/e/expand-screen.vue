<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn2j9uzdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wn2j9uzdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:expand-screen" /></template>
