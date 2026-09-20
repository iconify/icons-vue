<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfconw1ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfconw1ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:location-2" /></template>
