<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vczdkt4km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="vczdkt4km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-a" /></template>
