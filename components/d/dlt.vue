<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kidd-hbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kidd-hbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dlt" /></template>
