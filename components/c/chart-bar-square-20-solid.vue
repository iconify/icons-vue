<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vws5lwbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vws5lwbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chart-bar-square-20-solid" /></template>
