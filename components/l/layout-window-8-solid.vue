<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y02z66pwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y02z66pwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-8-solid" /></template>
