<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um1gt6bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="um1gt6bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:bbox" /></template>
