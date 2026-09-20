<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuca1sdhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuca1sdhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:cables-usb-type-c" /></template>
