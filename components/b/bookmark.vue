<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl30ird_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wl30ird_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bookmark" /></template>
