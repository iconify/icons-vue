<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo1krib8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo1krib8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floor-b" /></template>
