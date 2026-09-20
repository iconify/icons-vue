<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6ok2rj4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6ok2rj4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chat-bubble-typing-oval-solid" /></template>
