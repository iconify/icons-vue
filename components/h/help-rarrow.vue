<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqtld7bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="nqtld7bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:help-rarrow" /></template>
