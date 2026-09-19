<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxb4xp4od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uxb4xp4od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:flag" /></template>
