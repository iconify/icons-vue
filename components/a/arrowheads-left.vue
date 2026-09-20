<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laqm_x6nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="laqm_x6nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-left" /></template>
