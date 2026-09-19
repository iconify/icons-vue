<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cca125mqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cca125mqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclamation" /></template>
