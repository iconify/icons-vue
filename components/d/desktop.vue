<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dupq9r-yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1664};
const content = `<path class="dupq9r-yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:desktop" /></template>
