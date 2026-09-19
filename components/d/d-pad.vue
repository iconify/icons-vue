<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6ptorbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="h6ptorbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:d-pad" /></template>
