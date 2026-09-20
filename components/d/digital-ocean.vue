<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjwqdvbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fjwqdvbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:digital-ocean" /></template>
