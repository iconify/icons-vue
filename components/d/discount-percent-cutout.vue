<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isz0lobmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="isz0lobmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:discount-percent-cutout" /></template>
