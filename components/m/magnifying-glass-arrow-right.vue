<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl4uohhkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gl4uohhkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:magnifying-glass-arrow-right" /></template>
