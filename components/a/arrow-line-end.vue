<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdl_kk0km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mdl_kk0km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-end" /></template>
