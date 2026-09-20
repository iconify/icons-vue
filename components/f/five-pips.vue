<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzsuy0hik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nzsuy0hik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:five-pips" /></template>
