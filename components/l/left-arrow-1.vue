<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xknqbcc3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xknqbcc3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:left-arrow-1" /></template>
