<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzed_32fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzed_32fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-1-line" /></template>
