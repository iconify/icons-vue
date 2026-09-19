<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqpcc4bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bqpcc4bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell-16-solid" /></template>
