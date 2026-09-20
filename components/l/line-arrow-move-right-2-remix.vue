<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz40o_bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tz40o_bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-move-right-2-remix" /></template>
