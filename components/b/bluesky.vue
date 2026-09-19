<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_vp36uen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r_vp36uen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:bluesky" /></template>
