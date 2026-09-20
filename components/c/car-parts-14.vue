<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uawyetb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uawyetb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:car-parts-14" /></template>
