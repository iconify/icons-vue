<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz8x50brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rz8x50brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:magic-wand-2-remix" /></template>
