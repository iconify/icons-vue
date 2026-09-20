<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-6xlb0ma.css';
import '../../css/j/jxxo5_2qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-6xlb0ma"/><path class="jxxo5_2qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:home-assistant" /></template>
