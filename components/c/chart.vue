<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb8_pwp8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rb8_pwp8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:chart" /></template>
