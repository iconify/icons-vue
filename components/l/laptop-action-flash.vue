<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk95g98tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nk95g98tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:laptop-action-flash" /></template>
