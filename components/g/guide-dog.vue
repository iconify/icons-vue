<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2hgrbbwz.css';
import '../../css/c/cnr4z9ptg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="r2hgrbbwz"/><path class="cnr4z9ptg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:guide-dog" /></template>
