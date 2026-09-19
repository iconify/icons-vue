<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vngivucdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vngivucdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-behance" /></template>
