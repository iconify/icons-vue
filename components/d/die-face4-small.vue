<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0c8g-3wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b0c8g-3wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face4-small" /></template>
