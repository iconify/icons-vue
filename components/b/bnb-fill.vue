<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xas3exbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xas3exbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bnb-fill" /></template>
