<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz131qbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oz131qbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:left-arrow-circle" /></template>
