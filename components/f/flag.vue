<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p517mpiuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1536};
const content = `<path class="p517mpiuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:flag" /></template>
