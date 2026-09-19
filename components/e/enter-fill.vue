<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf3bt0b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zf3bt0b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:enter-fill" /></template>
