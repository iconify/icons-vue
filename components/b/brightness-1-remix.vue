<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyo2-_1op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tyo2-_1op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:brightness-1-remix" /></template>
