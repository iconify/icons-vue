<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-yawdb2x.css';
import '../../css/j/j5cb_7bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-yawdb2x"/><path class="j5cb_7bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:battery-alert" /></template>
