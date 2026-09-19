<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccbo3n_4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ccbo3n_4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:ellipsis-vertical" /></template>
