<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izjfx1-et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="izjfx1-et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-facebook" /></template>
