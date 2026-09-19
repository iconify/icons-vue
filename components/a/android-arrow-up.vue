<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp6vwabei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp6vwabei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-arrow-up" /></template>
