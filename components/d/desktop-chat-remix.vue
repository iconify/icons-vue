<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-muihb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-muihb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:desktop-chat-remix" /></template>
