<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxu7s1cmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mxu7s1cmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:invisible-1-remix" /></template>
