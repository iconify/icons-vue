<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ny-pb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u6ny-pb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:add" /></template>
