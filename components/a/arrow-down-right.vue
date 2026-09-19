<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz6vqmbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dz6vqmbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:arrow-down-right" /></template>
