<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epd4epbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="epd4epbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:anchor-circle-check" /></template>
