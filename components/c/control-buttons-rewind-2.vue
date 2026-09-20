<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4_hh9bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y4_hh9bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-rewind-2" /></template>
