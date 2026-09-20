<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrk17h_3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wrk17h_3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-text-square" /></template>
