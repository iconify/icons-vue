<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znn34tljo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znn34tljo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-right-up-bulk-round" /></template>
