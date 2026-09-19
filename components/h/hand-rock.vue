<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxibe2blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxibe2blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-rock" /></template>
