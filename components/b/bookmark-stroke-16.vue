<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf95xxbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lf95xxbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bookmark-stroke-16" /></template>
