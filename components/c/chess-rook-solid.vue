<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eba-jdbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eba-jdbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-rook-solid" /></template>
