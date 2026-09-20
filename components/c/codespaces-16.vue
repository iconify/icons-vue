<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxe-vkb4m.css';
import '../../css/v/vnwywmtwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mxe-vkb4m"/><path class="vnwywmtwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:codespaces-16" /></template>
