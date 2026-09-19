<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsd9tkbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gsd9tkbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:edit-1" /></template>
