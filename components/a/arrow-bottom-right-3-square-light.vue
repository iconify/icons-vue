<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn6nebcdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn6nebcdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-3-square-light" /></template>
