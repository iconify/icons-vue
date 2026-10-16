<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o04_3t6ej.css';
import '../../css/k/ktlm5_bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o04_3t6ej"/><path class="ktlm5_bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:current-transformer-20-bold" /></template>
