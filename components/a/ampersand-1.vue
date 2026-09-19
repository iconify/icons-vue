<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4sgr09lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a4sgr09lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ampersand-1" /></template>
