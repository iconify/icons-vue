<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4ztp3ont.css';
import '../../css/w/w093ptm_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u4ztp3ont"/><path class="w093ptm_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-cell-20" /></template>
