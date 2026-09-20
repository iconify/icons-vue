<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffoov4y2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ffoov4y2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:5-above-water" /></template>
