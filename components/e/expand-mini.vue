<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifxo9ybau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ifxo9ybau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:expand-mini" /></template>
