<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohnhlwhgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ohnhlwhgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cloud-download-solid" /></template>
