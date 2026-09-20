<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuko_16oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tuko_16oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-all" /></template>
