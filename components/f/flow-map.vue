<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2z2trbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="q2z2trbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:flow-map" /></template>
