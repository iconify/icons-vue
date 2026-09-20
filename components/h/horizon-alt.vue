<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckolh8b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ckolh8b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:horizon-alt" /></template>
