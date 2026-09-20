<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvxm07bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mvxm07bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-multiple-window-solid" /></template>
