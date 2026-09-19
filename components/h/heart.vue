<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-90pibdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="m-90pibdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:heart" /></template>
