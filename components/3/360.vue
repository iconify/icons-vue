<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_fpweb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="x_fpweb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:360" /></template>
