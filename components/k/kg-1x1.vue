<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0zgyobhy.css';
import '../../css/s/su9vssb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0zgyobhy"/><path class="su9vssb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:kg-1x1" /></template>
