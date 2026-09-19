<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2ruh8b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u2ruh8b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apex" /></template>
