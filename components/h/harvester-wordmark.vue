<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siao_abdn.css';
import '../../css/h/h1bx1sgau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="siao_abdn"/><path class="h1bx1sgau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:harvester-wordmark" /></template>
