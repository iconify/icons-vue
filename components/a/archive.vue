<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1y_4bigl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="f1y_4bigl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:archive" /></template>
