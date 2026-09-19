<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvcg5__wh.css';
import '../../css/z/z8-dohb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvcg5__wh"/><path class="z8-dohb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-check" /></template>
