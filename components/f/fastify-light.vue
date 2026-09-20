<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpsxk_bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":167.509};
const content = `<path class="wpsxk_bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fastify-light" /></template>
