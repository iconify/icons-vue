<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulgpg1p1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ulgpg1p1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:download-square-remix" /></template>
