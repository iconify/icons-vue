<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1-enbb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w1-enbb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:caret-up" /></template>
