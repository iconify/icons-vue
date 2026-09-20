<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx9jrebeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dx9jrebeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-tray-1-remix" /></template>
