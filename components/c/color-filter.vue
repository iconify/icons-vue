<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8qw21b7i.css';
import '../../css/d/dpo67b6zm.css';
import '../../css/z/z8_5hvbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l8qw21b7i"/><path class="dpo67b6zm"/><path class="z8_5hvbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:color-filter" /></template>
