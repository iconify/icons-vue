<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnm38wbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pnm38wbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-check-light" /></template>
