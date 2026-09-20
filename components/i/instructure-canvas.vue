<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ompyz3pxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ompyz3pxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instructure-canvas" /></template>
