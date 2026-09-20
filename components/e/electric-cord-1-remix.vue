<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt1xqdcmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dt1xqdcmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:electric-cord-1-remix" /></template>
