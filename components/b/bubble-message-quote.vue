<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnxdmobsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="qnxdmobsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bubble-message-quote" /></template>
