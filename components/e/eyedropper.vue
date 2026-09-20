<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv29y0z8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mv29y0z8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:eyedropper" /></template>
