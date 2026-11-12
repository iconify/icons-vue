<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8csb0gic.css';
import '../../css/m/m3dery5fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l8csb0gic"/><path class="m3dery5fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asp-net-core-dark" /></template>
