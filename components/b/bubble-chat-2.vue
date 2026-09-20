<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pittov07q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pittov07q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:bubble-chat-2" /></template>
