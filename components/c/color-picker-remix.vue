<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm7t13bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tm7t13bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:color-picker-remix" /></template>
