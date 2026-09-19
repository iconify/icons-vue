<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7vq71bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7vq71bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-bottom-center" /></template>
