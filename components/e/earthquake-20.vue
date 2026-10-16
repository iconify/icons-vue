<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wssriqbjc.css';
import '../../css/y/yvphjmmpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wssriqbjc"/><path class="yvphjmmpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earthquake-20" /></template>
