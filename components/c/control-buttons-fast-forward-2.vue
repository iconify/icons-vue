<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy4x7jter.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wy4x7jter"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-fast-forward-2" /></template>
