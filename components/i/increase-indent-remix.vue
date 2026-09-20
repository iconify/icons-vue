<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfng9b3mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wfng9b3mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:increase-indent-remix" /></template>
