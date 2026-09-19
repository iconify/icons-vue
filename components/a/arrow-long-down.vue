<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etbkadbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="etbkadbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-long-down" /></template>
