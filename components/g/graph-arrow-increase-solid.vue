<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjp1e-b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sjp1e-b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graph-arrow-increase-solid" /></template>
