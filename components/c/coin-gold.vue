<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nof6d3bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="nof6d3bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:coin-gold" /></template>
