<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww1159bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ww1159bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hierarchy-16-remix" /></template>
