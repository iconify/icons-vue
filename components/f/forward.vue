<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_a5qtbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y_a5qtbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:forward" /></template>
