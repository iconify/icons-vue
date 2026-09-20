<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvzyebcqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvzyebcqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:d3js-logo-block" /></template>
