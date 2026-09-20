<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyzg1pb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyzg1pb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:3-plus" /></template>
