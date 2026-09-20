<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0ds9_bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="l0ds9_bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:clipboard" /></template>
