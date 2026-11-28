<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fys4qbudi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fys4qbudi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:check-circle-multiple" /></template>
