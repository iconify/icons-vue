<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4auf4bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r4auf4bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-shrink-diagonal-2" /></template>
