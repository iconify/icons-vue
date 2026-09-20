<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulry8uluz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ulry8uluz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:die-face-with-one-pip" /></template>
