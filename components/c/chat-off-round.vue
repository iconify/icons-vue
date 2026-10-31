<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi8ws5jnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi8ws5jnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-round" /></template>
