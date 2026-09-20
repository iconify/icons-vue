<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se2jd0tlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="se2jd0tlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-outline-with-left-half-and-bottom-right-quarter" /></template>
