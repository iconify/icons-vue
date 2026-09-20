<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4vpdacjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r4vpdacjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chat-bubble-square-warning-remix" /></template>
