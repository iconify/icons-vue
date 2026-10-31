<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5a0avboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5a0avboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-minus-corner-fill-round" /></template>
