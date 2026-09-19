<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpr1c-b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="mpr1c-b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:folder-globe" /></template>
