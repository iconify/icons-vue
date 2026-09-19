<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1tgt3btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="e1tgt3btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:home" /></template>
