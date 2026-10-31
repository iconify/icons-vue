<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttfi1kb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttfi1kb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-x" /></template>
