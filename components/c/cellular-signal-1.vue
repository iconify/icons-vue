<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5ztg_ejc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ztg_ejc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cellular-signal-1" /></template>
