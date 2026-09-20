<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln56x6-6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ln56x6-6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-oval-smiley-1-solid" /></template>
