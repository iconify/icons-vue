<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_mykyb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_mykyb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amd-dark" /></template>
