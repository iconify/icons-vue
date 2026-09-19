<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isq-m5t3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isq-m5t3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:disease" /></template>
