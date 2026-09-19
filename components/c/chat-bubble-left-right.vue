<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqedi-bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqedi-bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-left-right" /></template>
