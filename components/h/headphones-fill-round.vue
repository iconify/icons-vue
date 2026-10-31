<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fngnv_hoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fngnv_hoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headphones-fill-round" /></template>
