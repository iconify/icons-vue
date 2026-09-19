<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss8d_8bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ss8d_8bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ink" /></template>
