<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1pgz2big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p1pgz2big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:chart-histogram" /></template>
