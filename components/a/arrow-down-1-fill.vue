<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab6tnjbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab6tnjbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-1-fill" /></template>
