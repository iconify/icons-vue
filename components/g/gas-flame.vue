<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgouwr_ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tgouwr_ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gas-flame" /></template>
