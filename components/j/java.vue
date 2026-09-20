<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqkgrobmp.css';
import '../../css/w/wh-3tcbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zqkgrobmp"/><path class="wh-3tcbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:java" /></template>
