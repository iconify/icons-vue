<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rctcol8zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":408};
const content = `<path class="rctcol8zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:city" /></template>
