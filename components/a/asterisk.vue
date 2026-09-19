<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy4mifo5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1536};
const content = `<path class="iy4mifo5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:asterisk" /></template>
