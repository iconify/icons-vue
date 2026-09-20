<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fghn1n5gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fghn1n5gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:football-ball" /></template>
