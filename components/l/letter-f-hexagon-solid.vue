<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5zgt7b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5zgt7b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-f-hexagon-solid" /></template>
