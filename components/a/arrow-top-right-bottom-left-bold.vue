<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm1lafg_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1lafg_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-right-bottom-left-bold" /></template>
