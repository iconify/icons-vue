<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhf5sybjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mhf5sybjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bars-3" /></template>
