<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnfo_0tdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tnfo_0tdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-move-remix" /></template>
