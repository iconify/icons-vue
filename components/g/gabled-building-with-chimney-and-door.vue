<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygo-ekbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ygo-ekbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-chimney-and-door" /></template>
