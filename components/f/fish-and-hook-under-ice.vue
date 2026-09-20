<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9mpb1lqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l9mpb1lqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-and-hook-under-ice" /></template>
