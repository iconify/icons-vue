<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdbkcyrsw.css';
import '../../css/c/c7_pmq9wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tdbkcyrsw"/><path class="c7_pmq9wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:1panel" /></template>
