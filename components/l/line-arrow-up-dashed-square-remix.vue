<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iptfli-wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iptfli-wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:line-arrow-up-dashed-square-remix" /></template>
