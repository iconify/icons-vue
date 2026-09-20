<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tntkyqb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tntkyqb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-up-right" /></template>
