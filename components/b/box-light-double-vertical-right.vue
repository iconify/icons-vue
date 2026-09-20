<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psx67-bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="psx67-bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-vertical-right" /></template>
