<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spw8_85nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spw8_85nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-fast-forward" /></template>
