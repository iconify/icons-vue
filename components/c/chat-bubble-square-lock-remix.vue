<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf38b-6ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zf38b-6ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-bubble-square-lock-remix" /></template>
