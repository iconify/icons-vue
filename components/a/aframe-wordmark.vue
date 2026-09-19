<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9auvtbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o9auvtbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:aframe-wordmark" /></template>
