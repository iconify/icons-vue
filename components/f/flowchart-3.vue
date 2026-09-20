<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poeuz0b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poeuz0b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:flowchart-3" /></template>
