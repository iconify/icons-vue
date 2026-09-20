<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh2n0hprc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qh2n0hprc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-right" /></template>
