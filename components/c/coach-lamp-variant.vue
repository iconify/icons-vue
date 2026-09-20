<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlp52tbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlp52tbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coach-lamp-variant" /></template>
