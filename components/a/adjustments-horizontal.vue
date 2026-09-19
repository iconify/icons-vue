<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdh9iubqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fdh9iubqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:adjustments-horizontal" /></template>
