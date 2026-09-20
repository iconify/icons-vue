<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh1vh8bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rh1vh8bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:business-progress-bar-2-solid" /></template>
