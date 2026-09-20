<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fups5pbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fups5pbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:i-in-circle" /></template>
