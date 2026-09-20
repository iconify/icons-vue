<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpbp98unh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpbp98unh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:astro" /></template>
