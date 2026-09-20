<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do-_nxtdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="do-_nxtdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ellipse" /></template>
