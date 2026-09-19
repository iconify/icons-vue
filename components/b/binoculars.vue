<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0nvo9bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m0nvo9bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:binoculars" /></template>
