<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf3i1lr5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf3i1lr5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:basketball-solid" /></template>
