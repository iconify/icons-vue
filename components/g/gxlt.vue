<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oew13ew-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oew13ew-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gxlt" /></template>
