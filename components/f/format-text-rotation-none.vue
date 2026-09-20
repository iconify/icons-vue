<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa3_k1b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa3_k1b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-rotation-none" /></template>
