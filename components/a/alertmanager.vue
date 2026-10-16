<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6hwt2o8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":115.333,"height":114};
const content = `<path class="r6hwt2o8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alertmanager" /></template>
