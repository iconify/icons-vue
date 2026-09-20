<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g19zyduic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g19zyduic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-reload-vertical-2-remix" /></template>
