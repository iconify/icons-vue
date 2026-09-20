<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zib-bfjpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zib-bfjpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:landscape-2-remix" /></template>
