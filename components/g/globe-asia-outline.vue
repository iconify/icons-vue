<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8bzxoi0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o8bzxoi0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-asia-outline" /></template>
