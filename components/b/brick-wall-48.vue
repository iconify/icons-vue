<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkr2umbbc.css';
import '../../css/y/yzb6z-b5r.css';
import '../../css/c/ct3eolbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vkr2umbbc"/><path class="yzb6z-b5r"/><path class="ct3eolbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brick-wall-48" /></template>
