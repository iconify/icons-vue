<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph08xqbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph08xqbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-tree-fill-round" /></template>
