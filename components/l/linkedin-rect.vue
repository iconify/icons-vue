<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbf30fbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="mbf30fbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:linkedin-rect" /></template>
