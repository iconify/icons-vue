<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1fp4ibvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":512};
const content = `<path class="v1fp4ibvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-beam-sweat" /></template>
