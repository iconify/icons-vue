<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfv2d1nvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="yfv2d1nvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:general-contractor" /></template>
