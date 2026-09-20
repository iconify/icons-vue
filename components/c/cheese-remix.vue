<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8b_w57wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z8b_w57wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cheese-remix" /></template>
