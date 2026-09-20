<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxprrt3ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="qxprrt3ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:funnel-1" /></template>
