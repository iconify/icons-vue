<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdcurrben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cdcurrben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chevron-circle-right" /></template>
