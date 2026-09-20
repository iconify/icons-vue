<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xykb5e5ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xykb5e5ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cpu" /></template>
