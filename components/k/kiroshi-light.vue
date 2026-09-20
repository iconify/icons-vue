<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0umoi1yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0umoi1yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kiroshi-light" /></template>
