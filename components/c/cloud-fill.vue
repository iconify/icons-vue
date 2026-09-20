<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh72ehbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wh72ehbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-fill" /></template>
