<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tntdz1o6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tntdz1o6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:line-arrow-reload-horizontal-2-remix" /></template>
