<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov260k97l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ov260k97l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:global-plant-filled" /></template>
