<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wssrv4thr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wssrv4thr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:landmark-flag" /></template>
