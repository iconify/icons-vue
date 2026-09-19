<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hifzu6bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hifzu6bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:expo-wordmark" /></template>
