<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz8egfbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jz8egfbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bag-with-percent" /></template>
