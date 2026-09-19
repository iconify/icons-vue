<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z48-j6bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z48-j6bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:camera-fill-12" /></template>
