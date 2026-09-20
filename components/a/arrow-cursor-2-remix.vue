<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzbu5zxuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kzbu5zxuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:arrow-cursor-2-remix" /></template>
