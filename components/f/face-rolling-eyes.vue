<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-9s02ozz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-9s02ozz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-rolling-eyes" /></template>
