<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciwla3dbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ciwla3dbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bug-virus-browser-remix" /></template>
