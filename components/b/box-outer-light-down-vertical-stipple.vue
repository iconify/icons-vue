<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v96ik30ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="v96ik30ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-down-vertical-stipple" /></template>
