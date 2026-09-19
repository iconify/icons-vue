<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnixs0bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wnixs0bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kibana" /></template>
