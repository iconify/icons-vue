<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgmfd2b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vgmfd2b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:fire-alarm-2-remix" /></template>
