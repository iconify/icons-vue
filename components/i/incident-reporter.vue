<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz58j3bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fz58j3bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:incident-reporter" /></template>
