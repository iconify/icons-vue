<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulh-6-blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulh-6-blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:coins-solid" /></template>
