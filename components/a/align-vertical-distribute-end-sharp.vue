<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dki60xbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dki60xbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-distribute-end-sharp" /></template>
