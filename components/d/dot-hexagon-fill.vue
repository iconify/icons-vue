<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip1i3acfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ip1i3acfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:dot-hexagon-fill" /></template>
