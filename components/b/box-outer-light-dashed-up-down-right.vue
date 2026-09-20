<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ick21ib3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ick21ib3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-up-down-right" /></template>
