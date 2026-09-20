<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jet3vgb5x.css';
import '../../css/i/ija69877e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jet3vgb5x"/><path class="ija69877e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:comments-reply" /></template>
