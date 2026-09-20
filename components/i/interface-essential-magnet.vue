<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn_jahutr.css';
import '../../css/q/qtvna5bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hn_jahutr"/><path class="qtvna5bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-magnet" /></template>
