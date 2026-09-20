<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lat4ssqys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lat4ssqys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:decent-work-and-economic-growth-solid" /></template>
