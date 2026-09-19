<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke8sr7biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ke8sr7biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:camera" /></template>
