<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_xjdlbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b_xjdlbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-bubble-text-square-remix" /></template>
