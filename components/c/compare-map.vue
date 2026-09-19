<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m319vub_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m319vub_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:compare-map" /></template>
