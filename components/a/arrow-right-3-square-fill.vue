<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv2zi2b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yv2zi2b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-3-square-fill" /></template>
