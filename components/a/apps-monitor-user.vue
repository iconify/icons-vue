<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6qfcegov.css';
import '../../css/q/qhe-99bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6qfcegov"/><path class="qhe-99bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:apps-monitor-user" /></template>
