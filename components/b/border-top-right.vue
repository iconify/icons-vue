<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylax2cbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ylax2cbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-top-right" /></template>
