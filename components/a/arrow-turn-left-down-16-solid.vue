<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxgm09bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fxgm09bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-down-16-solid" /></template>
