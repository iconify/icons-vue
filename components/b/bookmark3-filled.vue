<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwj9zrqlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwj9zrqlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark3-filled" /></template>
