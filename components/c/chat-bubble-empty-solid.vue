<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbyvz2pfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbyvz2pfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-empty-solid" /></template>
