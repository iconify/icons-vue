<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu06u1-hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uu06u1-hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-3-fill" /></template>
