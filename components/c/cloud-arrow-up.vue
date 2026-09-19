<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/squd2zbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="squd2zbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cloud-arrow-up" /></template>
