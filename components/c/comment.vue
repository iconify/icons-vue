<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz6p_b0ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz6p_b0ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:comment" /></template>
