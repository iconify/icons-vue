<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg5t6pbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lg5t6pbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-oval-left-20-solid" /></template>
