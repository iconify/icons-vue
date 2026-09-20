<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4ab1wb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4ab1wb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:layers-1-remix" /></template>
