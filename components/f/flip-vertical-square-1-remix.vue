<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsrgl4t2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsrgl4t2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flip-vertical-square-1-remix" /></template>
