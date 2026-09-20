<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrm7coa1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qrm7coa1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:front-camera-remix" /></template>
