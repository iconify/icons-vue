<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypzybbb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ypzybbb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chart-bar-20-solid" /></template>
