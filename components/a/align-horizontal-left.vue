<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_a1hrbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="z_a1hrbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:align-horizontal-left" /></template>
