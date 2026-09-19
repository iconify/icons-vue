<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa-a1_bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="oa-a1_bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-net" /></template>
