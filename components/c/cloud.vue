<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrw5sjivn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw5sjivn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:cloud" /></template>
