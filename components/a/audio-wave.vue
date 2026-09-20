<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-fmv1bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="w-fmv1bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:audio-wave" /></template>
