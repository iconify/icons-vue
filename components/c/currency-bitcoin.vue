<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q48u-cbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q48u-cbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:currency-bitcoin" /></template>
