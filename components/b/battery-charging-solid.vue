<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfu7chbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vfu7chbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:battery-charging-solid" /></template>
