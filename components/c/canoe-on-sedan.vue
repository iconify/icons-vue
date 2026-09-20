<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufnv-ab8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ufnv-ab8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-on-sedan" /></template>
