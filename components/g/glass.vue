<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lok1r60yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lok1r60yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:glass" /></template>
