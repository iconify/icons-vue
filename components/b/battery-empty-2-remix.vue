<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdiwa3b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdiwa3b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:battery-empty-2-remix" /></template>
