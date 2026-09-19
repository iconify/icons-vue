<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvcg5__wh.css';
import '../../css/k/k4r099b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvcg5__wh"/><path class="k4r099b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-error" /></template>
