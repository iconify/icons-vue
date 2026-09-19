<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa740y-ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wa740y-ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:chat-bubble-bottom-center-text" /></template>
