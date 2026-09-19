<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofe-j50dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ofe-j50dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-triangle-right" /></template>
