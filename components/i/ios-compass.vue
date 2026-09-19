<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcgwv7b1e.css';
import '../../css/x/xjkzlbbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lcgwv7b1e"/><path class="xjkzlbbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-compass" /></template>
