<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr_470bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr_470bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:italic" /></template>
