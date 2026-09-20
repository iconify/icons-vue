<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8bdsc6ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o8bdsc6ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-oval-notification-solid" /></template>
