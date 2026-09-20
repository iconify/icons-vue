<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7fznlbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l7fznlbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bulbed-star" /></template>
