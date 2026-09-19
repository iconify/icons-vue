<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sruux_bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="sruux_bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-oval-left-ellipsis-20-solid" /></template>
