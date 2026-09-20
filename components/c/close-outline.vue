<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1w81wbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p1w81wbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:close-outline" /></template>
