<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdnq2ffxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdnq2ffxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:app-window-minus" /></template>
