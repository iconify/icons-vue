<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syqzq4b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="syqzq4b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-vertical-horizontal" /></template>
