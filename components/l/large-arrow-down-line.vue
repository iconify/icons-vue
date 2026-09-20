<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5xpi3wfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5xpi3wfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-down-line" /></template>
