<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0z8ph33h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1536};
const content = `<path class="m0z8ph33h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:lightbulb-o" /></template>
