<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6v956x8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6v956x8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-bulk-round" /></template>
