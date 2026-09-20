<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi0wmscgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fi0wmscgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ferris-wheel" /></template>
