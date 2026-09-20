<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz63_s8wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wz63_s8wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-down-right-stipple" /></template>
