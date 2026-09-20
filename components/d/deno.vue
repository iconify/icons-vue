<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn277tbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn277tbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:deno" /></template>
