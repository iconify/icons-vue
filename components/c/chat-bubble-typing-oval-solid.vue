<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyn48u6gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eyn48u6gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-typing-oval-solid" /></template>
