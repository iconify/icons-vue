<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbbc40btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbbc40btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:live-line" /></template>
