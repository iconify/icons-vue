<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmi81oi2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":480};
const content = `<path class="jmi81oi2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:attachment-alt" /></template>
