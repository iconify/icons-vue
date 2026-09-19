<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwp_z2i8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mwp_z2i8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-vertical-center-two" /></template>
