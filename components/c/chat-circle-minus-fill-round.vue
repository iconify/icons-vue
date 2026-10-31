<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7oac0bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7oac0bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-minus-fill-round" /></template>
