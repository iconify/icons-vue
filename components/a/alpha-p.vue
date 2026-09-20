<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx1qx3tfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qx1qx3tfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-p" /></template>
