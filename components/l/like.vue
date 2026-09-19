<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wss56ybga.css';
import '../../css/p/p3ixe5bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="wss56ybga"/><path class="p3ixe5bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:like" /></template>
