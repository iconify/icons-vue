<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt3m2bate.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt3m2bate"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-check-round" /></template>
