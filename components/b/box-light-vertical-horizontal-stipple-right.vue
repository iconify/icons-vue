<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slc0ckb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="slc0ckb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-right" /></template>
