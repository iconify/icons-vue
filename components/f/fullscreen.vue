<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn2jxfbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wn2jxfbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:fullscreen" /></template>
