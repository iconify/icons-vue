<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3utnwbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":480};
const content = `<path class="t3utnwbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:eject" /></template>
