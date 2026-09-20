<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_lr62wnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_lr62wnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:investing-and-banking-solid" /></template>
