<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqpcagbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jqpcagbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-minimize-window-1-remix" /></template>
