<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfivj4bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfivj4bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chess-knight-remix" /></template>
