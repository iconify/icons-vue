<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwgagrk5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vwgagrk5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:download" /></template>
