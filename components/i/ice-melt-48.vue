<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdpmiccce.css';
import '../../css/i/i6it53bol.css';
import '../../css/i/i1z6z-v6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdpmiccce"/><path class="i6it53bol"/><path class="i1z6z-v6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-melt-48" /></template>
