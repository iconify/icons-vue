<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_8zx3bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k_8zx3bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:home" /></template>
