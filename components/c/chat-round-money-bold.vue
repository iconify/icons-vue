<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5da1fblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5da1fblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-money-bold" /></template>
