<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-1t6y5ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-1t6y5ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-reload-vertical-1-remix" /></template>
