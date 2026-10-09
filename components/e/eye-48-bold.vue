<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybb_vebim.css';
import '../../css/w/wdaa5te7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ybb_vebim"/><path class="wdaa5te7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-48-bold" /></template>
