<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrje97bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lrje97bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-plus-in-solid" /></template>
