<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwowx4blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vwowx4blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:connecticut-with-capital-star" /></template>
