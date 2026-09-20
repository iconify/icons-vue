<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik9kr5b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ik9kr5b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-up-stipple-up-left" /></template>
