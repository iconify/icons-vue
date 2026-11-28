<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lybym4bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lybym4bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-left-light" /></template>
