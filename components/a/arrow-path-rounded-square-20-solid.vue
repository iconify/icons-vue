<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db9fy1bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="db9fy1bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-path-rounded-square-20-solid" /></template>
