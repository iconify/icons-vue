<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbe5hy7tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xbe5hy7tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dollar-coin-1-remix" /></template>
