<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w511s810q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w511s810q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:landscape-2-remix" /></template>
