<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agydmcrgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agydmcrgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:heart-suit" /></template>
