<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0g1y97nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f0g1y97nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:3d" /></template>
