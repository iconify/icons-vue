<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgj8a8b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xgj8a8b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dark-dislay-mode-remix" /></template>
