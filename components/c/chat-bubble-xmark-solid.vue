<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucu-4jbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucu-4jbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-xmark-solid" /></template>
