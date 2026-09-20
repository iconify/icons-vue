<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdggodk-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zdggodk-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:like-1-remix" /></template>
