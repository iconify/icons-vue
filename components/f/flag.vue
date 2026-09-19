<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_2fxrbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="l_2fxrbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:flag" /></template>
