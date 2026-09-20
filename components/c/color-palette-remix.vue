<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orrp5pbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="orrp5pbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:color-palette-remix" /></template>
