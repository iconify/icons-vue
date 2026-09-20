<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-xkov5aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="o-xkov5aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-stipple-right" /></template>
