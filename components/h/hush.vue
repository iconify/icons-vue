<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdhf0yb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vdhf0yb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:hush" /></template>
