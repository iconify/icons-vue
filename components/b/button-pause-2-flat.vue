<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5x8obe1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x5x8obe1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:button-pause-2-flat" /></template>
