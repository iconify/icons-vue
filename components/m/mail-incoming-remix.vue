<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5fxf3tgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j5fxf3tgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-incoming-remix" /></template>
