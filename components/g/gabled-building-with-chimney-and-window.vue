<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb4moactm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zb4moactm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-chimney-and-window" /></template>
