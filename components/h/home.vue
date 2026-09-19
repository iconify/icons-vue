<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy1j1mu6r.css';
import '../../css/q/qmrmd-8xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yy1j1mu6r"/><path class="qmrmd-8xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:home" /></template>
