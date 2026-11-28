<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0tsj9bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m0tsj9bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-bottom-fill" /></template>
