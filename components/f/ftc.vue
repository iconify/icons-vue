<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i50sb8b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i50sb8b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ftc" /></template>
