<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_x_evmre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_x_evmre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-down-line" /></template>
