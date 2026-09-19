<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm7-icbdt.css';
import '../../css/f/fl5j57bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tm7-icbdt"/><path class="fl5j57bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:dribbble" /></template>
