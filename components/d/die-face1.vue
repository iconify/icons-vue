<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyiugab0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dyiugab0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face1" /></template>
