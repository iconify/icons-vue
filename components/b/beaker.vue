<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xex2wub0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xex2wub0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker" /></template>
