<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spfb3wbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spfb3wbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevrons-horizontal-2" /></template>
