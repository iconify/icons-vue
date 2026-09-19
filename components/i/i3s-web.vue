<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwrycbbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vwrycbbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:i3s-web" /></template>
