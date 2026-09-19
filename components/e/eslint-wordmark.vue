<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2lb21bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u2lb21bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:eslint-wordmark" /></template>
