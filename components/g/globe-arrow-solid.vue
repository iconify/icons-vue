<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oohom20oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oohom20oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:globe-arrow-solid" /></template>
