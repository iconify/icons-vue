<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmtew4bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":112,"height":384};
const content = `<path class="qmtew4bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:caret-left" /></template>
