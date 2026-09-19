<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjh7xxbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hjh7xxbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:carpentry-saw" /></template>
