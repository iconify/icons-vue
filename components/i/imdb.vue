<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wordb69qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wordb69qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:imdb" /></template>
