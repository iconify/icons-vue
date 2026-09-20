<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_y1t0b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_y1t0b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:columns" /></template>
