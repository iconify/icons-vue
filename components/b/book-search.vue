<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5oob6yvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5oob6yvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-search" /></template>
