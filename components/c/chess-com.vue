<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7majck1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b l7majck1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:chess-com" /></template>
