<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7c98za8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="o7c98za8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-1" /></template>
