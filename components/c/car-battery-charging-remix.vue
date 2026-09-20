<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb7gbybnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cb7gbybnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:car-battery-charging-remix" /></template>
