<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruu_5mhlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruu_5mhlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-square-code" /></template>
