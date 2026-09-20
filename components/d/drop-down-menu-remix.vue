<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxe-m3zen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxe-m3zen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:drop-down-menu-remix" /></template>
