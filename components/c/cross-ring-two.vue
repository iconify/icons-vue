<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwl69gbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hwl69gbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cross-ring-two" /></template>
