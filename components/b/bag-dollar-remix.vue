<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0st4ubeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0st4ubeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bag-dollar-remix" /></template>
