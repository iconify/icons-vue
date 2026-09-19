<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaueldbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gaueldbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:green-square" /></template>
