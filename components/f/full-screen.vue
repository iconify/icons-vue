<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqmje5bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hqmje5bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:full-screen" /></template>
