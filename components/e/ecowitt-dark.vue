<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfetpsbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfetpsbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ecowitt-dark" /></template>
