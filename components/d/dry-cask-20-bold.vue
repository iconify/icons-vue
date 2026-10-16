<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8tgbj8rv.css';
import '../../css/g/glfmzd9iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f8tgbj8rv"/><path class="glfmzd9iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dry-cask-20-bold" /></template>
