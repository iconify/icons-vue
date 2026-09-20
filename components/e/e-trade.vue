<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zykmcsy6u.css';
import '../../css/c/cf4rmeasd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zykmcsy6u"/><path class="cf4rmeasd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:e-trade" /></template>
