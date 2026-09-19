<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjvk998zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rjvk998zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:ampersand-1" /></template>
