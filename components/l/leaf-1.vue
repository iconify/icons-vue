<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk0acybbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lk0acybbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:leaf-1" /></template>
