<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5x-zjtyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j5x-zjtyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:magic-wand-2-remix" /></template>
