<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5-q7tbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5-q7tbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-oval-left" /></template>
