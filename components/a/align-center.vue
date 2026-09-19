<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw4dz4bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sw4dz4bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-center" /></template>
