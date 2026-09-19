<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow7yq4bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ow7yq4bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bars-arrow-down" /></template>
