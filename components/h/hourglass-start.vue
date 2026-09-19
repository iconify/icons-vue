<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp4eqjvst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="mp4eqjvst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hourglass-start" /></template>
