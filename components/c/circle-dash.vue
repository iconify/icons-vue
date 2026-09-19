<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg0-lccqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rg0-lccqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:circle-dash" /></template>
