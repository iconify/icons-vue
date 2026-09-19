<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjeo1t3ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="jjeo1t3ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:google-buzz" /></template>
