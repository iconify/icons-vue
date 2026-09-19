<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rar3t3bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rar3t3bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:magnifying-glass" /></template>
