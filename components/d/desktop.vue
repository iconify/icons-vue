<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjqaxibet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vjqaxibet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:desktop" /></template>
