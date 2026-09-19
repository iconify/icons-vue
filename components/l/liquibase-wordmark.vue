<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-ujdc4dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c-ujdc4dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:liquibase-wordmark" /></template>
