<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic87zvbqj.css';
import '../../css/h/h-plcb8jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ic87zvbqj"/><path class="h-plcb8jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:consulting" /></template>
