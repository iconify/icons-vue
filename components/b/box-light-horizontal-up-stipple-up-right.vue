<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st72lkbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="st72lkbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-up-stipple-up-right" /></template>
