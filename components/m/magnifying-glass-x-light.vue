<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0zabj_tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c0zabj_tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:magnifying-glass-x-light" /></template>
