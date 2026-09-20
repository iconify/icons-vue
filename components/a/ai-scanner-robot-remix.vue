<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f21smdbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f21smdbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:ai-scanner-robot-remix" /></template>
