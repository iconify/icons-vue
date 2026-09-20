<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvuqs7byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvuqs7byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:box" /></template>
