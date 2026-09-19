<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxg2sfops.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pxg2sfops"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:laptop" /></template>
