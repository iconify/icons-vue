<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0efq_bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="m0efq_bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:adonisjs-wordmark" /></template>
