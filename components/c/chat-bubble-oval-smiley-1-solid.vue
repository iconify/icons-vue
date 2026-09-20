<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5ezajb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m5ezajb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-bubble-oval-smiley-1-solid" /></template>
