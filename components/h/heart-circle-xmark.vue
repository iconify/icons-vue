<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvg6d5bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gvg6d5bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:heart-circle-xmark" /></template>
