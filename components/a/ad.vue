<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1er8ya1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1er8ya1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ad" /></template>
