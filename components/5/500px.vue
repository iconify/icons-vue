<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wav8b0bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wav8b0bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:500px" /></template>
