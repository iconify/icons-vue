<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdowv-q2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdowv-q2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-bottom-center-solid" /></template>
