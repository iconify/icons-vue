<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo62-ybxn.css';
import '../../css/q/qxpl-b1jp.css';
import '../../css/y/yghwv6byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xo62-ybxn"/><path class="qxpl-b1jp"/><path class="yghwv6byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-slow-20-bold" /></template>
