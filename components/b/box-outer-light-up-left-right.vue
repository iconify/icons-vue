<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz98gcbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="xz98gcbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-left-right" /></template>
