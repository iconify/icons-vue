<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woe447n8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="woe447n8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hard-drive-1-remix" /></template>
