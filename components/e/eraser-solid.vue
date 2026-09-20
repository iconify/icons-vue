<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh8mkbcfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xh8mkbcfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:eraser-solid" /></template>
