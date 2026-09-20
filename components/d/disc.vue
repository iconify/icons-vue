<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5nu14clm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h5nu14clm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:disc" /></template>
