<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2pacqbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k2pacqbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:conifer-tree-with-star-and-ornaments" /></template>
