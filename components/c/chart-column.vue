<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkg5wobjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkg5wobjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-column" /></template>
