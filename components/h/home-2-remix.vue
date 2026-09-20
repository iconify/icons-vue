<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvxp1d9fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hvxp1d9fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:home-2-remix" /></template>
