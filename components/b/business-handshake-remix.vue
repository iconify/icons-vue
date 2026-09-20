<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3u2rabta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q3u2rabta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:business-handshake-remix" /></template>
