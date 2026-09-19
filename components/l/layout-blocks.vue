<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft97n1bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft97n1bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:layout-blocks" /></template>
