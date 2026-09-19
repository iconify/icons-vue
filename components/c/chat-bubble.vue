<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbqaqi79s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qbqaqi79s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chat-bubble" /></template>
