<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twrtpeqih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="twrtpeqih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:graticule-globe" /></template>
