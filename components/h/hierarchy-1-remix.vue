<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7sn5tbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i7sn5tbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hierarchy-1-remix" /></template>
