<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6l_spbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u6l_spbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:image-plus" /></template>
