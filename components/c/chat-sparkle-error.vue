<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j042-s57z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j042-s57z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chat-sparkle-error" /></template>
