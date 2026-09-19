<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrpor5pjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrpor5pjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:fire-extinguisher" /></template>
