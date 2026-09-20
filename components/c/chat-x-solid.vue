<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1quw3brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1quw3brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-x-solid" /></template>
