<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdr5pxbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sdr5pxbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bat" /></template>
