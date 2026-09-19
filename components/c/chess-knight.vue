<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmr10_dtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="cmr10_dtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:chess-knight" /></template>
