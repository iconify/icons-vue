<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qua7fvb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qua7fvb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:four-of-circles-mahjong-filled" /></template>
