<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5z51jagi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="q5z51jagi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chalkboard" /></template>
